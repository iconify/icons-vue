<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_w_6xb3l.css';
import '../../css/f/f7n_6objg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_w_6xb3l"/><path class="f7n_6objg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-plus-solid" /></template>

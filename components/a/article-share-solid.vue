<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_w_6xb3l.css';
import '../../css/n/njxe4acos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_w_6xb3l"/><path class="njxe4acos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-share-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk67lgbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk67lgbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-small-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyi5jwbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="zyi5jwbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drag-vertical-solid" /></template>

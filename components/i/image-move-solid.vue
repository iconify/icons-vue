<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whl2ggbnv.css';
import '../../css/z/zxqlfdc4u.css';
import '../../css/d/dw105c7vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whl2ggbnv"/><path clip-rule="evenodd" class="zxqlfdc4u"/><path class="dw105c7vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-move-solid" /></template>

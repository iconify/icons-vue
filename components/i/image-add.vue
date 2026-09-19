<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yibyn6bhe.css';
import '../../css/f/fxqkr7b2w.css';
import '../../css/v/viznwcc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yibyn6bhe"/><path class="fxqkr7b2w"/><path class="viznwcc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:image-add" /></template>

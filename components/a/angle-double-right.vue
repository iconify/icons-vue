<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf9t8jb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf9t8jb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:angle-double-right" /></template>

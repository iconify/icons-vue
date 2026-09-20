<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cisucrfdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cisucrfdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-masonry-line" /></template>

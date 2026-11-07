<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq8bxxi9p.css';
import '../../css/i/iads9dnva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8bxxi9p"/><path class="iads9dnva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-star-bold-duotone" /></template>

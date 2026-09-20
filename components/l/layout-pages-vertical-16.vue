<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p29vpb_np.css';
import '../../css/j/jp5u-n8ve.css';
import '../../css/l/l8htvablp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p29vpb_np"/><path class="jp5u-n8ve"/><path class="l8htvablp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:layout-pages-vertical-16" /></template>

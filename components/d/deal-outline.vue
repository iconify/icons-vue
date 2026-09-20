<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peu9dxqux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="peu9dxqux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:deal-outline" /></template>

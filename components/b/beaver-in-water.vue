<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha54we7vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ha54we7vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:beaver-in-water" /></template>

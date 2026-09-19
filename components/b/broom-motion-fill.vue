<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx6kogx4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zx6kogx4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:broom-motion-fill" /></template>

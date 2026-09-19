<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eap8ov2yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eap8ov2yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-play-fill" /></template>

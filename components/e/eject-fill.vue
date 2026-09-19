<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec1-kobqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ec1-kobqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:eject-fill" /></template>

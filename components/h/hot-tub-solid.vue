<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-yfogdgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d-yfogdgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hot-tub-solid" /></template>

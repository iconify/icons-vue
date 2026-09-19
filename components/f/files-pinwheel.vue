<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqeckf5cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eqeckf5cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:files-pinwheel" /></template>

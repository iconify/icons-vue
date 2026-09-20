<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnn5m5bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xnn5m5bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:car-side-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma39lbb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ma39lbb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:landmark-solid" /></template>

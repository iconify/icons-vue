<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3yvj_ezw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k3yvj_ezw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:help-buoy-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gce1dr0xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gce1dr0xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-add-2-line" /></template>

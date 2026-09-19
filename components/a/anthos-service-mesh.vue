<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx3tnd3zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx3tnd3zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:anthos-service-mesh" /></template>

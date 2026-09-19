<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecsfs2btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ecsfs2btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:atlas" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soa9m9aph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soa9m9aph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ampersands-line" /></template>

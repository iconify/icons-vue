<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6mvl4wxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6mvl4wxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ev-charge" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozfwejbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozfwejbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:download-04" /></template>

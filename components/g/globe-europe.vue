<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0mdim-6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="e0mdim-6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:globe-europe" /></template>

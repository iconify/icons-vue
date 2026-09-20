<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0tlg44yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0tlg44yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-left-from-line" /></template>

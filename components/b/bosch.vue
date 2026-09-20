<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kief4lrfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kief4lrfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bosch" /></template>

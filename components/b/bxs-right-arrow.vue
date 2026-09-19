<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajl4pv1wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajl4pv1wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-right-arrow" /></template>

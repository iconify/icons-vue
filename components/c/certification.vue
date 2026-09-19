<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3_-5is-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3_-5is-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:certification" /></template>

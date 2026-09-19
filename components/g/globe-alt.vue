<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ccfwb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_ccfwb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-alt" /></template>

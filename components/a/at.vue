<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gds_2f.css';
import '../../css/s/so-from-86.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gds_2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:at" /></template>

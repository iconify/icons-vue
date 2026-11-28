<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3729jbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3729jbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:car-x" /></template>

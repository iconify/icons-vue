<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfs22gbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfs22gbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:code" /></template>

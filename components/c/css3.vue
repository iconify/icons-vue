<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om12kcc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om12kcc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:css3" /></template>

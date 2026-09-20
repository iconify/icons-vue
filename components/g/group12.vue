<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd-z39bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd-z39bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:group12" /></template>

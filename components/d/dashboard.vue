<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc1infp9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc1infp9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:dashboard" /></template>

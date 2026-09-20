<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od0cxibja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od0cxibja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-slash" /></template>

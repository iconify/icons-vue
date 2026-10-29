<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tet6-1b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tet6-1b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:at-sign-solid" /></template>

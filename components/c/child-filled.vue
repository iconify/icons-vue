<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quhy5abwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quhy5abwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:child-filled" /></template>

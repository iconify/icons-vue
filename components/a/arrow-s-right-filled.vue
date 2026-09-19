<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooffe2bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooffe2bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-s-right-filled" /></template>

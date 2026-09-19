<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esuh9ulmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esuh9ulmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-all-filled" /></template>

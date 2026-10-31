<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faxv8eb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faxv8eb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chocolate-box-gloss" /></template>

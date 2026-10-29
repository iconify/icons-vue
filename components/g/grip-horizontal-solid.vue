<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e16a-gbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e16a-gbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grip-horizontal-solid" /></template>

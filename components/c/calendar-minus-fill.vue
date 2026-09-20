<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_uink9fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_uink9fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-minus-fill" /></template>

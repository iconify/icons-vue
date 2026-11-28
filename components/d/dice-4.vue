<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2c66yxnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2c66yxnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dice-4" /></template>

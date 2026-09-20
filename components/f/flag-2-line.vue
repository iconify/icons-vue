<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgssn1xut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgssn1xut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-2-line" /></template>

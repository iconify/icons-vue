<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeg-uebww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeg-uebww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:linear-fill" /></template>

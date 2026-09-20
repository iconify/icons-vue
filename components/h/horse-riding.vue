<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwe_38duk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwe_38duk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horse-riding" /></template>

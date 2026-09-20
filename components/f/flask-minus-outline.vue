<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mej7m02qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mej7m02qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-minus-outline" /></template>

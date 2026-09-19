<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oirxshbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="oirxshbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:indent" /></template>

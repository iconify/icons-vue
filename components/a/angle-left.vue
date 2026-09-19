<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdjq0irqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdjq0irqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-left" /></template>

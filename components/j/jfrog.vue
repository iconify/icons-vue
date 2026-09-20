<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbq3xlb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbq3xlb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jfrog" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ent8d6byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ent8d6byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:foxtel" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue7j03b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue7j03b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amul" /></template>

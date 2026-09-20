<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdpdfwpsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdpdfwpsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:home-2-filled" /></template>

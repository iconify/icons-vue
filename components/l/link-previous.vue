<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmb7g3bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmb7g3bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:link-previous" /></template>

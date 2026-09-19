<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhglolbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhglolbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:help-circle-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvq12eqif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvq12eqif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bubbles-solid" /></template>

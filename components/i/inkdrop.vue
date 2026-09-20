<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coz-zacrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coz-zacrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:inkdrop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eft6sfbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eft6sfbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lg-air-purifier" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnoy0zbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnoy0zbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:linuxserver" /></template>

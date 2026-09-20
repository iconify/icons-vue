<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emvcfcssn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emvcfcssn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:device-laptop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg3p42byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg3p42byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-j-bulk-round" /></template>

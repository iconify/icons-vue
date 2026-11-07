<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr006pb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr006pb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-stack-broken" /></template>

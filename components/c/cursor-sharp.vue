<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sme5tdrez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sme5tdrez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-sharp" /></template>

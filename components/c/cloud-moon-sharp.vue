<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xahm4zbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xahm4zbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-moon-sharp" /></template>

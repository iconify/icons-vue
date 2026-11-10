<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdfu3-prn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdfu3-prn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-exclamation" /></template>

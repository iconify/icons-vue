<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guc1_jbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="guc1_jbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:identification-card" /></template>

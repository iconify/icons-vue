<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glfd-obwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glfd-obwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-tc-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m74ql-csp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="m74ql-csp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-circle-up-left" /></template>

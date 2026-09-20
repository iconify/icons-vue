<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es3s4jbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es3s4jbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jira" /></template>

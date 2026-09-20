<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvypm0e2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvypm0e2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-check-error" /></template>

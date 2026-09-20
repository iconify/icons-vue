<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5act16ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5act16ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-left-2-line" /></template>

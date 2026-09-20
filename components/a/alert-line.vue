<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e06csukwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e06csukwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:alert-line" /></template>

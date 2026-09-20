<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emf8wccme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="emf8wccme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkbox-component-checked" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nne51pr0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nne51pr0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:basket" /></template>

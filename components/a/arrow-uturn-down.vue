<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npa4pmb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npa4pmb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-down" /></template>

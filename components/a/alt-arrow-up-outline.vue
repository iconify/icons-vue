<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhx05rsiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhx05rsiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-up-outline" /></template>

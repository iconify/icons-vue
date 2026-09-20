<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bazfj2bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bazfj2bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-menu-fill" /></template>

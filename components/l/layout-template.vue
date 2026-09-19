<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwbi8czbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwbi8czbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layout-template" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvvllvbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvvllvbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-up-arrow-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/govcx3bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="govcx3bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:factr" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g08z-jbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g08z-jbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:info-shield-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpa4a0bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpa4a0bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-right-solid" /></template>

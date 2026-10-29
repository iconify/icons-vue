<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8l_9bbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8l_9bbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-solid" /></template>

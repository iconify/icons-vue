<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceq1he5nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ceq1he5nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cursor-arrow-ripple-solid" /></template>

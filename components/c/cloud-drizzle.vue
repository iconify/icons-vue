<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or5y5jvbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or5y5jvbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-drizzle" /></template>

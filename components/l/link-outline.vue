<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k176_rbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k176_rbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:link-outline" /></template>

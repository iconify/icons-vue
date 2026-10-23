<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok6ud3bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok6ud3bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-sun-rain" /></template>

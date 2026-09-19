<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn0gp5bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn0gp5bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fire-solid" /></template>

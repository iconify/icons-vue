<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dok-f4htb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dok-f4htb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bone-solid" /></template>

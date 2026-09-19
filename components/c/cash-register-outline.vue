<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2d394ajk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2d394ajk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cash-register-outline" /></template>

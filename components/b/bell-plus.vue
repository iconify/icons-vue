<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj0_rabtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0_rabtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bell-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d103kcbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d103kcbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airbrakedotio" /></template>

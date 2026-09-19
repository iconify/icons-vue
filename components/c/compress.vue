<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shnqu1q9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shnqu1q9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:compress" /></template>

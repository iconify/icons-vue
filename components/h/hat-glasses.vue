<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9vfuu1bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9vfuu1bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hat-glasses" /></template>

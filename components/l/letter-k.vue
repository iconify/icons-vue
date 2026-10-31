<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-j-jjbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-j-jjbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-k" /></template>

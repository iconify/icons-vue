<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isi942u_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="isi942u_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:android" /></template>

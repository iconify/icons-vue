<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq_6npb_q.css';
import '../../css/m/mkkiv_s3q.css';
import '../../css/d/d61yiac4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq_6npb_q"/><path class="mkkiv_s3q"/><path class="d61yiac4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cup-paper-bold" /></template>

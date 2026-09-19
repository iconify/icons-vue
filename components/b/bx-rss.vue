<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffkma_bxg.css';
import '../../css/o/ob3ntmvsq.css';
import '../../css/h/hntz4fq6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffkma_bxg"/><path class="ob3ntmvsq"/><circle class="hntz4fq6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-rss" /></template>

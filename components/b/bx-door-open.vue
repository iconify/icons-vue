<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgxd4gqfq.css';
import '../../css/i/iaz7k-bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgxd4gqfq"/><path class="iaz7k-bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-door-open" /></template>

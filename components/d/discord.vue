<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/k/knqoax.css';
import '../../css/n/nl5zqf.css';
import '../../css/m/mgwdvu.css';
import '../../css/s/s-756n.css';
import '../../css/j/jtgu8n.css';
import '../../css/s/so-from-32.css';
import '../../css/s/so-to-0.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-1_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c knqoax"/><path class="a0m25c nl5zqf"/><circle class="mgwdvu s-756n"/><circle class="jtgu8n s-756n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:discord" /></template>

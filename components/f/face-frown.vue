<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usr8d0vnk.css';
import '../../css/m/my-g78bbf.css';
import '../../css/i/ibd18pb0y.css';
import '../../css/u/uvm8k6bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usr8d0vnk"/><path class="my-g78bbf"/><circle class="ibd18pb0y"/><circle class="uvm8k6bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:face-frown" /></template>

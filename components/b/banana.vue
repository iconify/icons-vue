<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q11bnobfu.css';
import '../../css/l/lec51cbbz.css';
import '../../css/i/ipk8v9b_s.css';
import '../../css/c/cq97wwbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q11bnobfu"/><path class="lec51cbbz"/><path class="ipk8v9b_s"/><path class="cq97wwbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:banana" /></template>

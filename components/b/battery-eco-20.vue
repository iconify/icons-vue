<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5fpfqrkj.css';
import '../../css/g/gg61wfd5d.css';
import '../../css/x/xb12bpbpj.css';
import '../../css/f/ft4db_bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5fpfqrkj"/><path class="gg61wfd5d"/><path class="xb12bpbpj"/><path class="ft4db_bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-eco-20" /></template>

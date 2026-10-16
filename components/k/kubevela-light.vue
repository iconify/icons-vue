<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltuu1s2eo.css';
import '../../css/q/qu5j37bnx.css';
import '../../css/b/bg_cubciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":122.5,"height":122.5};
const content = `<path class="ltuu1s2eo"/><path class="qu5j37bnx"/><path class="bg_cubciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kubevela-light" /></template>

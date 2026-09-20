<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op63yotmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="op63yotmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:balance-scale-right-solid" /></template>

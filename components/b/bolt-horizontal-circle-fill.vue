<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4wra6ukb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w4wra6ukb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-horizontal-circle-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcekv60qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcekv60qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:balance-scale" /></template>

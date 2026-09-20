<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5buxdvyt.css';
import '../../css/o/objm-ccgw.css';
import '../../css/w/w_5g2gbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z5buxdvyt"/><path class="objm-ccgw"/><path class="w_5g2gbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cogs" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_s_snbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ae_s_snbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-global" /></template>

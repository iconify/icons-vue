<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwhunbto.css';
import '../../css/c/c3l2dyibj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ciwhunbto"/><path class="c3l2dyibj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:enter" /></template>

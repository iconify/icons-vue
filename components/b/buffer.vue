<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hncin7bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hncin7bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:buffer" /></template>

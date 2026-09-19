<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk-_s_bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lk-_s_bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:discover" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv-rjdbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":496};
const content = `<path class="xv-rjdbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:machine-wash-gentle-or-delicate" /></template>

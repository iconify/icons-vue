<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo3-ksbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="oo3-ksbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:database" /></template>

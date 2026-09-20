<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iorepnbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="iorepnbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bi-cycle" /></template>

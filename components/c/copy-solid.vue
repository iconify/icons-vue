<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udf4sdb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udf4sdb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-solid" /></template>

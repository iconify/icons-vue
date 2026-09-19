<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzqkn_xju.css';
import '../../css/q/q-on95byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzqkn_xju"/><path class="q-on95byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:deno" /></template>

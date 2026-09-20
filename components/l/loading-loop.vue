<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqogua.css';
import '../../css/t/tr-2c6-rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqogua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:loading-loop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usrx4ob1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usrx4ob1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:auto-hold-line" /></template>

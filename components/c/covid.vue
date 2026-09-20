<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdbpxmjmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdbpxmjmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:covid" /></template>

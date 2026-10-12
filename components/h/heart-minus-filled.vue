<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikrl6obvt.css';
import '../../css/o/omixov_3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikrl6obvt"/><path class="omixov_3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-minus-filled" /></template>

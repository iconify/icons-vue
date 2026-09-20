<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5xxn-bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5xxn-bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:dollar-sign" /></template>

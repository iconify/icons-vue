<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6d1tt4vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6d1tt4vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:desk-lamp-2-line" /></template>

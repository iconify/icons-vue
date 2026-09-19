<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b92jmp90d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b92jmp90d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:aviato" /></template>

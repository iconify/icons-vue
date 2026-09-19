<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxyrztbdj.css';
import '../../css/h/h2egwczhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxyrztbdj"/><path class="h2egwczhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-right-circle" /></template>

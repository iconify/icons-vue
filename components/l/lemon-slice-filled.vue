<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqe58787v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqe58787v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lemon-slice-filled" /></template>

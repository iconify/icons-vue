<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx2a4vdax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx2a4vdax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cspr" /></template>

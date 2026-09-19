<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7wz_k0tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7wz_k0tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-closed" /></template>

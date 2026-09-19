<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej_yigban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_yigban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-alt-2-filled" /></template>

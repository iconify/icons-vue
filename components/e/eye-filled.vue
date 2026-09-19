<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kba9m842r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kba9m842r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-filled" /></template>

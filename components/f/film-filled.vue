<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozb0_ubof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozb0_ubof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:film-filled" /></template>

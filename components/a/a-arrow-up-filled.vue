<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyzm1ebos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyzm1ebos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:a-arrow-up-filled" /></template>

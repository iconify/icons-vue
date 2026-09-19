<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch77nccom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch77nccom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-alt-2" /></template>

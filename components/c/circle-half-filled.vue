<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlznznb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlznznb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-half-filled" /></template>

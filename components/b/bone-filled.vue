<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lludr_bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lludr_bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bone-filled" /></template>

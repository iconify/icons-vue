<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjy99ybww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjy99ybww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:computer-add" /></template>

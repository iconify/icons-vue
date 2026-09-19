<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgkic680g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkic680g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:feather-plus-filled" /></template>

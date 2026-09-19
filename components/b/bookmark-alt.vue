<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf19ixb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf19ixb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-alt" /></template>

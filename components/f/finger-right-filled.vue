<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhl9vvbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhl9vvbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-right-filled" /></template>

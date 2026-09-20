<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxcbvvf1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxcbvvf1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-bottom-left-filled" /></template>

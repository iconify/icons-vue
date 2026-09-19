<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpuhgxbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpuhgxbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:florist-filled" /></template>

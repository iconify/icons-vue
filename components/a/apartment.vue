<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nik7msbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nik7msbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:apartment" /></template>

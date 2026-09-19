<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6um3cbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6um3cbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-alt-filled" /></template>

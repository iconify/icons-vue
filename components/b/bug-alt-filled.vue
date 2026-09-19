<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc9z1mbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc9z1mbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bug-alt-filled" /></template>

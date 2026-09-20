<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv9eqyb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv9eqyb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:filter-clear-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-f4ob-1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-f4ob-1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-down-circle-fill" /></template>

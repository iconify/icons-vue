<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8v583a5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8v583a5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-left-down-fill" /></template>

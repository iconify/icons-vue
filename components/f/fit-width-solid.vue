<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6i__-bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6i__-bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fit-width-solid" /></template>

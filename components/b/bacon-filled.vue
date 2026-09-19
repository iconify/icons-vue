<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5g9zdbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5g9zdbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bacon-filled" /></template>

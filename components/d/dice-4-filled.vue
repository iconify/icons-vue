<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct79oziwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct79oziwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dice-4-filled" /></template>

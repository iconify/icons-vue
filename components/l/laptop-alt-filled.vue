<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2wycibyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2wycibyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laptop-alt-filled" /></template>

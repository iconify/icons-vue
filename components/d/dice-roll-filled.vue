<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_4qgcb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_4qgcb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dice-roll-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx3v0_qti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx3v0_qti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-pull-request-closed-filled" /></template>

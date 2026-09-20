<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv4-_kbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv4-_kbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-plus-filled" /></template>

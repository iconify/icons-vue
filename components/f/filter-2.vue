<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2ljocb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2ljocb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:filter-2" /></template>

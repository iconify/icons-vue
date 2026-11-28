<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5mn7quir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5mn7quir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bluetooth-solid" /></template>

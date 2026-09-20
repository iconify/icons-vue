<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tplsg9b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tplsg9b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-pin" /></template>

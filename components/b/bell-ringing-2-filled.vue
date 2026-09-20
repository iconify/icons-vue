<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8omf1bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8omf1bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-ringing-2-filled" /></template>

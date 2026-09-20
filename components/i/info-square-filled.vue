<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgq6q4bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgq6q4bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:info-square-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhnit_bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhnit_bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-chevrons-down-up" /></template>

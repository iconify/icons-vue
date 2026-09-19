<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grp69rnla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grp69rnla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:exchange-01" /></template>

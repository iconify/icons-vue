<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqa16qcmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqa16qcmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chess-01" /></template>

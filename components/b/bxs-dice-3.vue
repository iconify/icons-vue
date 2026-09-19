<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfdj0-b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfdj0-b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dice-3" /></template>

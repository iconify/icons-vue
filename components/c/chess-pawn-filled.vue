<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxz985mfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxz985mfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-pawn-filled" /></template>

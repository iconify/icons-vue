<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq0ba4bnx.css';
import '../../css/f/fu6wn7bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq0ba4bnx"/><path class="fu6wn7bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:door-closed-package-filled" /></template>

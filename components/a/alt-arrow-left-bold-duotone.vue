<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctf7tpbxx.css';
import '../../css/i/i_23a8b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctf7tpbxx"/><path class="i_23a8b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-bold-duotone" /></template>

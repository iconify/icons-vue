<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm0pbmbno.css';
import '../../css/o/o_b_sl5zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cm0pbmbno"/><path class="o_b_sl5zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ansible-lint" /></template>

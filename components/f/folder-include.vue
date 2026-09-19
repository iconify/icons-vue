<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roar_qb4z.css';
import '../../css/b/bwck-2bqv.css';
import '../../css/x/x804q6kvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="roar_qb4z"/><circle class="bwck-2bqv"/><path class="x804q6kvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-include" /></template>

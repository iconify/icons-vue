<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12ji_bzg.css';
import '../../css/p/pgzvnfbvt.css';
import '../../css/r/r--b2dpcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><circle class="pgzvnfbvt"/><path class="r--b2dpcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-private-open" /></template>

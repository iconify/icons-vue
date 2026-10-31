<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfvcz_evv.css';
import '../../css/q/q03fz5bjx.css';
import '../../css/l/ldkk9pbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="tfvcz_evv"/><path class="q03fz5bjx"/><path class="ldkk9pbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:chad" /></template>

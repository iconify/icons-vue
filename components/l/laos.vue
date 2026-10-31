<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl8d8wbcz.css';
import '../../css/m/md1p39bnd.css';
import '../../css/w/waflsubxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nl8d8wbcz"/><path class="md1p39bnd"/><path class="waflsubxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:laos" /></template>

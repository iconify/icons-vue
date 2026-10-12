<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx50cdblo.css';
import '../../css/s/skotkdb7i.css';
import '../../css/k/keplz_bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx50cdblo"/><path class="skotkdb7i"/><path class="keplz_bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:goal-filled" /></template>

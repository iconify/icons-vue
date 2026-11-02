<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mniiu69wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mniiu69wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-10-fill" /></template>

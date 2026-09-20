<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6iq297bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6iq297bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calculator-filled" /></template>

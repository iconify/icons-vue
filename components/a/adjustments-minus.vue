<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7e5-73sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7e5-73sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-minus" /></template>

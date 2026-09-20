<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgw_fbc9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgw_fbc9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-left-rhombus-filled" /></template>

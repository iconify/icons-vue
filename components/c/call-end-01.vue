<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejytsk_lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejytsk_lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-end-01" /></template>

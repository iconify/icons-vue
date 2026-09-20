<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dixvrabtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dixvrabtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-check-warning-filled" /></template>

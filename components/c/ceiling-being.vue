<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keu3it29w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keu3it29w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-being" /></template>

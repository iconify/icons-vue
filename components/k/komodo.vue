<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnai2pbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnai2pbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:komodo" /></template>

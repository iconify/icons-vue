<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv2gc5bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv2gc5bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-minus-corner-round" /></template>

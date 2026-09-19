<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc75m8d8n.css';
import '../../css/t/tzev64bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mc75m8d8n"/><path class="tzev64bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:credit-card" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waxeanb4e.css';
import '../../css/m/mgns90b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waxeanb4e"/><path class="mgns90b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:exclamation-mark-bold-duotone" /></template>

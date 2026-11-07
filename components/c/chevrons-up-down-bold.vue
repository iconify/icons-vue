<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7lymocvt.css';
import '../../css/g/gx3w35u0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7lymocvt"/><path class="gx3w35u0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-up-down-bold" /></template>

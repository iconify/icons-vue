<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl-h9o8md.css';
import '../../css/e/eclqm_bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-h9o8md"/><path class="eclqm_bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-to-line-bold-duotone" /></template>

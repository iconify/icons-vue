<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9xycefpv.css';
import '../../css/w/w9ster-bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9xycefpv"/><path class="w9ster-bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-bing-bold-duotone" /></template>

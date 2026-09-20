<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxivi6frs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kxivi6frs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:compact-disc-filled" /></template>

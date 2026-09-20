<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi0z0b6-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi0z0b6-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:exposure-plus-1" /></template>

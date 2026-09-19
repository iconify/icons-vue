<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz-ruebpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz-ruebpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-top-01" /></template>

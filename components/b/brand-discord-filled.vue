<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg13oeb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg13oeb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-discord-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pib3_sb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pib3_sb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:join-straight" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4fgg8b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4fgg8b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-patreon-filled" /></template>

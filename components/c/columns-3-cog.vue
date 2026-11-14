<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voe_oxz9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voe_oxz9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:columns-3-cog" /></template>

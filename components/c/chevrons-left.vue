<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkib5uw3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkib5uw3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevrons-left" /></template>

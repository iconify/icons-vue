<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd90nbc5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd90nbc5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-half-2" /></template>

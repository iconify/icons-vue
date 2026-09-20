<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtjnp5e0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjnp5e0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-bluesky" /></template>

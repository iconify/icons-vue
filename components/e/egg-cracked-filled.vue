<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udsm0l3hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udsm0l3hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:egg-cracked-filled" /></template>

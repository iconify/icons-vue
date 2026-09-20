<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8p4rekmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8p4rekmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplets-filled" /></template>

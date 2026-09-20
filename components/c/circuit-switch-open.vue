<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pobxyue2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pobxyue2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-switch-open" /></template>

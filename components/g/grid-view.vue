<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0jrx045d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0jrx045d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:grid-view" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcssw9n5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcssw9n5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local" /></template>

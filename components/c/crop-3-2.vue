<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2-4v5bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-4v5bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-3-2" /></template>

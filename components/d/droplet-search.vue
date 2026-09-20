<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jajk6c28e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jajk6c28e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-search" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctnjq6b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctnjq6b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-search" /></template>

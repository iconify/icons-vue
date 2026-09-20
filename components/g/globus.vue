<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p47rngo5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p47rngo5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:globus" /></template>

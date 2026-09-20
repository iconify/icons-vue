<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu7x4t4ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu7x4t4ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-discount" /></template>

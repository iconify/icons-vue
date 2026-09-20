<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r14uh_74t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r14uh_74t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-edit" /></template>

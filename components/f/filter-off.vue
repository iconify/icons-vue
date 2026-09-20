<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii5fitmfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii5fitmfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-off" /></template>

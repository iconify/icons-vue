<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf9o9n5rb.css';
import '../../css/k/kpz-x8bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf9o9n5rb"/><path clip-rule="evenodd" class="kpz-x8bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-2-outline" /></template>

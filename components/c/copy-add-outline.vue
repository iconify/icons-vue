<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od8vdsbvc.css';
import '../../css/e/egvbavgae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od8vdsbvc"/><path clip-rule="evenodd" class="egvbavgae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-add-outline" /></template>

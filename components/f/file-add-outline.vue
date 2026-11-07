<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu85f6s0m.css';
import '../../css/d/d25mwn3tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu85f6s0m"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-add-outline" /></template>

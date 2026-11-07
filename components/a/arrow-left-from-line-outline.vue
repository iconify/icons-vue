<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmgit0fdl.css';
import '../../css/b/bfch-tf9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmgit0fdl"/><path class="bfch-tf9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-from-line-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abtab-k7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abtab-k7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-bug-outline" /></template>

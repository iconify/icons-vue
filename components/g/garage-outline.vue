<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-osjzzli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-osjzzli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:garage-outline" /></template>

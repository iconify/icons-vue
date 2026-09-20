<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsxxn0dfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsxxn0dfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-check-outline" /></template>

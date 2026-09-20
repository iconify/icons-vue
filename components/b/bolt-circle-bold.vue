<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc-3-bc9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gc-3-bc9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-circle-bold" /></template>

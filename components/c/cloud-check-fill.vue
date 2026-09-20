<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q96z7vg-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q96z7vg-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-check-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y32u2fimd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y32u2fimd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hdmi-port-filled" /></template>

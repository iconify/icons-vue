<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_eyv71ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_eyv71ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:command-outline" /></template>

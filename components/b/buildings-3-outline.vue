<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbx5hlb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbx5hlb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-3-outline" /></template>

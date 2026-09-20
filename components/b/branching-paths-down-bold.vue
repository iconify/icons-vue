<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9ztmfnrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g9ztmfnrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-down-bold" /></template>

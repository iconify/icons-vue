<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt7ztxbrk.css';
import '../../css/k/k-_v8bbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt7ztxbrk"/><path class="k-_v8bbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:hard-disk-storage-filled" /></template>

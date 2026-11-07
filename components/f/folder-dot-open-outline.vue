<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szmhgzb0a.css';
import '../../css/p/pphqfabzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szmhgzb0a"/><path clip-rule="evenodd" class="pphqfabzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-dot-open-outline" /></template>

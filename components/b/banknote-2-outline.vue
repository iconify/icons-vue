<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_zr_mbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_zr_mbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-2-outline" /></template>

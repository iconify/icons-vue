<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_h7sufq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_h7sufq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-forbid-fill" /></template>

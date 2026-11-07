<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy2l7ab8f.css';
import '../../css/i/i6ux3gi0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy2l7ab8f"/><path class="i6ux3gi0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:incoming-call-rounded-outline" /></template>

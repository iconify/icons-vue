<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uno68zbmk.css';
import '../../css/d/dvq72viog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uno68zbmk"/><path class="dvq72viog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carton-off-filled" /></template>

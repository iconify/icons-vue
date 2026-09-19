<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cee5qpbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cee5qpbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lens-convex" /></template>

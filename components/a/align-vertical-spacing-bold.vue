<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6st3otec.css';
import '../../css/c/c14tr3b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6st3otec"/><path class="c14tr3b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-spacing-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rotba7baa.css';
import '../../css/c/c52h3c0el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rotba7baa"/><path class="c52h3c0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizonta-spacing-bold-duotone" /></template>

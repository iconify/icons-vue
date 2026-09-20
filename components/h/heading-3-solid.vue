<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efz6zcc6h.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efz6zcc6h"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:heading-3-solid" /></template>

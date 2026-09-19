<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1t73q-cv.css';
import '../../css/k/kisx4ib0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1t73q-cv duoicon-secondary-layer"/><path class="duoicon-primary-layer kisx4ib0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:baby-carriage" /></template>

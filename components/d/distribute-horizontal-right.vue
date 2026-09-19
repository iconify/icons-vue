<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bucsvihvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bucsvihvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:distribute-horizontal-right" /></template>

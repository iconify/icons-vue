<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln-hxshjc.css';
import '../../css/o/oiqop8ebf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln-hxshjc"/><path class="oiqop8ebf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-close-outline" /></template>

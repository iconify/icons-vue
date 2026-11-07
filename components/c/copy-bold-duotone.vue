<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwfa9_-5x.css';
import '../../css/m/mtplmt03a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwfa9_-5x"/><path class="mtplmt03a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-bold-duotone" /></template>

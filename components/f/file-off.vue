<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwto3nb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwto3nb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:file-off" /></template>

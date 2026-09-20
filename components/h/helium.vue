<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1g_hup3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1g_hup3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:helium" /></template>

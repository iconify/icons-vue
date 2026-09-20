<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz1d02xod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz1d02xod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-code" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk3oz7bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk3oz7bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cell-signal-off" /></template>

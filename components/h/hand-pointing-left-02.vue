<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5ch-dc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ch-dc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-left-02" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgpqfv2kb.css';
import '../../css/p/pp7u04bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgpqfv2kb"/><path class="pp7u04bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:alarm-outline" /></template>

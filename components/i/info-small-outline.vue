<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez2ebpnon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ez2ebpnon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:info-small-outline" /></template>

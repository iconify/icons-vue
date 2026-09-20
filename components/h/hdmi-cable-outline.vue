<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juxektbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="juxektbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hdmi-cable-outline" /></template>

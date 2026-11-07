<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gswtq35or.css';
import '../../css/r/r10rxstew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gswtq35or"/><path class="r10rxstew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-add-angle-bold-duotone" /></template>

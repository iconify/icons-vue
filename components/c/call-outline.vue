<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj4wi1bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bj4wi1bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:call-outline" /></template>

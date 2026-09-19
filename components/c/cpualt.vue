<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si8w2mlyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="si8w2mlyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cpualt" /></template>

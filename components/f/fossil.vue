<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-fmy342m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":449,"height":512};
const content = `<path class="q-fmy342m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fossil" /></template>

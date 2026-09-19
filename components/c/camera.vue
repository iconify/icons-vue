<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gonmgov-i.css';
import '../../css/s/s1ew34b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="gonmgov-i"/><path class="s1ew34b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:camera" /></template>

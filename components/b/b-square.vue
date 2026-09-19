<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azc0-rwwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="azc0-rwwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:b-square" /></template>

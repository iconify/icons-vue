<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhhac4b9m.css';
import '../../css/a/a2-rokb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhhac4b9m"/><path class="a2-rokb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:arc" /></template>

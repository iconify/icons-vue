<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umn48nmev.css';
import '../../css/o/oz88olb9k.css';
import '../../css/k/kc2kqxrec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="umn48nmev"/><path class="oz88olb9k"/><path class="kc2kqxrec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compressor-48-bold" /></template>

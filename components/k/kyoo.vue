<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl69lcchu.css';
import '../../css/o/otmkmnc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl69lcchu"/><path class="otmkmnc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kyoo" /></template>

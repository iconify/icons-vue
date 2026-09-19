<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggv24lm0s.css';
import '../../css/q/qki1cds-o.css';
import '../../css/s/s6aioybet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ggv24lm0s"/><path class="duoicon-primary-layer qki1cds-o"/><path class="duoicon-primary-layer s6aioybet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:g-translate" /></template>

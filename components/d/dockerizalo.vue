<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgkqhtgri.css';
import '../../css/e/enl7e7b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgkqhtgri"/><path class="enl7e7b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockerizalo" /></template>

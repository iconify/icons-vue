<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrl_9-k9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hrl_9-k9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:file-tray" /></template>

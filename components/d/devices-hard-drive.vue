<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oniaw-bgi.css';
import '../../css/p/pva-szciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oniaw-bgi"/><path clip-rule="evenodd" class="pva-szciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-hard-drive" /></template>

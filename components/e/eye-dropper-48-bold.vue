<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlosulb6e.css';
import '../../css/b/b9isaca6x.css';
import '../../css/b/bfo_vpyhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wlosulb6e"/><path class="b9isaca6x"/><path class="bfo_vpyhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-dropper-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v16uh-byn.css';
import '../../css/s/sahyts8de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v16uh-byn"/><path class="sahyts8de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hiking-48" /></template>

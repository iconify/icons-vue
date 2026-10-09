<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chwqx0x_b.css';
import '../../css/f/fm25kwqqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="chwqx0x_b"/><path class="fm25kwqqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:briefcase-48" /></template>

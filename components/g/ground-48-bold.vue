<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpggqk6re.css';
import '../../css/e/e75wleedx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jpggqk6re"/><path class="e75wleedx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-48-bold" /></template>

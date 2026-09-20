<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_9cc6bpa.css';
import '../../css/g/gwt9xds0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_9cc6bpa"/><path class="gwt9xds0b ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-app-search" /></template>

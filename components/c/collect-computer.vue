<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qka82ly9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qka82ly9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:collect-computer" /></template>

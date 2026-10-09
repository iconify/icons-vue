<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaxcsz8rc.css';
import '../../css/r/rzy0o9f7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aaxcsz8rc"/><path class="rzy0o9f7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cheese-48" /></template>

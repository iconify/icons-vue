<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b68xxsbdc.css';
import '../../css/q/qs2jqdb-s.css';
import '../../css/j/j46k23i9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b68xxsbdc"/><path class="qs2jqdb-s"/><path class="j46k23i9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dna-48" /></template>

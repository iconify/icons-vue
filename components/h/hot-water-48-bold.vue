<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0fqkdb-z.css';
import '../../css/z/zrpz3wb1c.css';
import '../../css/s/soun1mbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s0fqkdb-z"/><path class="zrpz3wb1c"/><path class="soun1mbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-water-48-bold" /></template>

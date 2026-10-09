<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbu-t6btd.css';
import '../../css/h/hg1lnachy.css';
import '../../css/r/ry46iabfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="hg1lnachy"/><path class="ry46iabfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-square-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lelyizmit.css';
import '../../css/s/spkgakbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lelyizmit"/><path class="spkgakbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-tub-48-bold" /></template>

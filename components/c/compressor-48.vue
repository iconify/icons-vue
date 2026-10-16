<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnw5nvftm.css';
import '../../css/q/q177d-m0y.css';
import '../../css/h/h7hp1q67c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lnw5nvftm"/><path class="q177d-m0y"/><path class="h7hp1q67c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compressor-48" /></template>

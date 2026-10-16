<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk7d7db1k.css';
import '../../css/i/iq3tm2n6h.css';
import '../../css/u/uhrotbb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sk7d7db1k"/><path class="iq3tm2n6h"/><path class="uhrotbb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-alarm-48" /></template>

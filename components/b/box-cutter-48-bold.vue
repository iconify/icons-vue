<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpslvk5st.css';
import '../../css/u/umkdqbblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qpslvk5st"/><path class="umkdqbblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:box-cutter-48-bold" /></template>

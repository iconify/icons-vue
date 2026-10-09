<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilg_98b5z.css';
import '../../css/r/r9g8q-bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ilg_98b5z"/><path class="r9g8q-bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-48-bold" /></template>

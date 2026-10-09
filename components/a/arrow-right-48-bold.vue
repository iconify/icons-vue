<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilg_98b5z.css';
import '../../css/z/z5ckwp2dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ilg_98b5z"/><path class="z5ckwp2dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-48-bold" /></template>

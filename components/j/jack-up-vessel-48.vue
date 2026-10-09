<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm-6ijbqa.css';
import '../../css/k/k3_wrxi7z.css';
import '../../css/d/d90gdxket.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fm-6ijbqa"/><path class="k3_wrxi7z"/><path class="d90gdxket"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jack-up-vessel-48" /></template>

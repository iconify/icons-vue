<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba29q_65m.css';
import '../../css/f/f1favznrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ba29q_65m"/><path class="f1favznrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockbox-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh22bq98t.css';
import '../../css/x/x37i8o26b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fh22bq98t"/><path class="x37i8o26b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-48" /></template>

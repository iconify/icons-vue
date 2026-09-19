<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rimzogy_d.css';
import '../../css/x/xkpcfdb4u.css';
import '../../css/h/hasg0ee8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rimzogy_d"/><path class="xkpcfdb4u"/><circle class="hasg0ee8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:info" /></template>

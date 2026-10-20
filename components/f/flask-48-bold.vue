<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3fwuybqi.css';
import '../../css/b/bg063jb_r.css';
import '../../css/q/q-95t6xiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c3fwuybqi"/><path class="bg063jb_r"/><path class="q-95t6xiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flask-48-bold" /></template>

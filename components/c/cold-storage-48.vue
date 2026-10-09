<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lji_pzt1f.css';
import '../../css/y/ymlv-kbac.css';
import '../../css/m/mg7ihkb7k.css';
import '../../css/d/d-rurg29d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lji_pzt1f"/><path class="ymlv-kbac"/><path class="mg7ihkb7k"/><path class="d-rurg29d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cold-storage-48" /></template>

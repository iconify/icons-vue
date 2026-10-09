<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m69v3r-fa.css';
import '../../css/m/m0f-csihk.css';
import '../../css/o/o8iczsb-w.css';
import '../../css/a/agdapachy.css';
import '../../css/r/rh9ticcru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m69v3r-fa"/><path class="m0f-csihk"/><path class="o8iczsb-w"/><path class="agdapachy"/><path class="rh9ticcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bulldozer-20-bold" /></template>

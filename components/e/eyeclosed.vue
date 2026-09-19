<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znvs6w-8g.css';
import '../../css/d/d2zz1uo2x.css';
import '../../css/l/l5j5uofki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="znvs6w-8g"/><path class="d2zz1uo2x"/><path class="l5j5uofki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:eyeclosed" /></template>

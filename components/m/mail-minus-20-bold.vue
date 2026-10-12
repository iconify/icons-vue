<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvpdrtm6x.css';
import '../../css/k/kgx7jsbsk.css';
import '../../css/h/hayl1lfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lvpdrtm6x"/><path class="kgx7jsbsk"/><path class="hayl1lfmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-minus-20-bold" /></template>

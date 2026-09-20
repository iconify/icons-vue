<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynyh7db1r.css';
import '../../css/t/th8xxac7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ynyh7db1r"/><path class="th8xxac7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bank-11" /></template>

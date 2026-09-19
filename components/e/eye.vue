<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shexgfo6g.css';
import '../../css/o/oin-52btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="shexgfo6g"/><path class="oin-52btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eye" /></template>

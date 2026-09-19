<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el07r1zqo.css';
import '../../css/o/oelx92bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="el07r1zqo"/><path class="oelx92bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:construct" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ftmugmu.css';
import '../../css/t/t2zrok28c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2ftmugmu"/><path class="t2zrok28c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:healthlog-dark" /></template>

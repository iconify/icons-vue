<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljkqsabqw.css';
import '../../css/k/k8gf3yb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljkqsabqw"/><path class="k8gf3yb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackskullcrossbones" /></template>

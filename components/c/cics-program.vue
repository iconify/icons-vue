<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_j9e2b0e.css';
import '../../css/e/eqzj32bze.css';
import '../../css/b/bgok00bat.css';
import '../../css/z/zwkqv9-qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d_j9e2b0e"/><circle class="eqzj32bze"/><circle class="bgok00bat"/><path class="zwkqv9-qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-program" /></template>

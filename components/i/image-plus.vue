<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q17t251rw.css';
import '../../css/y/yvf9cwdfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q17t251rw"/><path class="yvf9cwdfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:image-plus" /></template>

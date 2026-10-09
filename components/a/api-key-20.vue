<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3i9_lhj.css';
import '../../css/x/x_1bpc-0g.css';
import '../../css/q/qdghjzejf.css';
import '../../css/c/c5hkgdbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lq3i9_lhj"/><path class="x_1bpc-0g"/><path class="qdghjzejf"/><path class="c5hkgdbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:api-key-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm4miebwu.css';
import '../../css/k/kbtpf3fuc.css';
import '../../css/g/gcdi2ob1m.css';
import '../../css/o/oaxr94b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zm4miebwu"/><path class="kbtpf3fuc"/><path class="gcdi2ob1m"/><path class="oaxr94b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:heart-with-arrow" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3fwb-27e.css';
import '../../css/o/owlnadbcb.css';
import '../../css/k/kbe_yhbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3fwb-27e"/><rect class="owlnadbcb"/><path class="kbe_yhbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:library" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvm03rryn.css';
import '../../css/h/h_1byfbub.css';
import '../../css/k/kv9lofb8u.css';
import '../../css/b/b2i4qcwof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvm03rryn"/><path class="h_1byfbub"/><path class="kv9lofb8u"/><path class="b2i4qcwof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:languages-48" /></template>

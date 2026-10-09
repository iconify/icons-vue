<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d938krbry.css';
import '../../css/e/eid02wl-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d938krbry"/><path class="eid02wl-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crop-20" /></template>

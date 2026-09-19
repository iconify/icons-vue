<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9jnc9b3h.css';
import '../../css/l/l83296b_y.css';
import '../../css/g/gv7hefb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z9jnc9b3h"/><path class="l83296b_y"/><circle class="gv7hefb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:ipad" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdvsm5ash.css';
import '../../css/s/sm0fnnq5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rdvsm5ash"/><path class="sm0fnnq5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:child" /></template>

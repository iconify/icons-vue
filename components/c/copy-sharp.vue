<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhwkk-pks.css';
import '../../css/s/spak13bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhwkk-pks"/><path class="spak13bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:copy-sharp" /></template>

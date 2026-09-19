<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si-zo371a.css';
import '../../css/r/rpw047bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="si-zo371a"/><path class="rpw047bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:link-alt" /></template>

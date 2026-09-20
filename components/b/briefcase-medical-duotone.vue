<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2-9wig_g.css';
import '../../css/k/kow831b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2-9wig_g"/><path class="kow831b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcase-medical-duotone" /></template>

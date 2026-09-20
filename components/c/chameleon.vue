<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/ny87dobof.css';
import '../../css/g/gtc2uzbxu.css';
import '../../css/d/d8wygibdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ny87dobof"/><circle class="gtc2uzbxu"/><path class="d8wygibdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:chameleon" /></template>

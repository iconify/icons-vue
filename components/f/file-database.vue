<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pmwdljh8p.css';
import '../../css/g/gaqp2k4re.css';
import '../../css/k/kac42ebbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pmwdljh8p"/><path class="gaqp2k4re"/><path class="kac42ebbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:file-database" /></template>

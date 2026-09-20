<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v8bnwkbre.css';
import '../../css/u/u43r19bom.css';
import '../../css/j/j5mopbbpq.css';
import '../../css/s/shu3xdl9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v8bnwkbre"/><path class="u43r19bom"/><path class="j5mopbbpq"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:loader-pinwheel" /></template>

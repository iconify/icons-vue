<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0s-ac9h.css';
import '../../css/l/lm02t2s9x.css';
import '../../css/d/d3wazpbzu.css';
import '../../css/e/erivwsp2x.css';
import '../../css/m/mrn8wkozq.css';
import '../../css/e/eaixb3h3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="un0s-ac9h"/><path class="lm02t2s9x"/><circle class="d3wazpbzu"/><path class="erivwsp2x"/><circle class="mrn8wkozq"/><path class="eaixb3h3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:children-crossing" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/m/m98gijb1j.css';
import '../../css/t/t9pa4cczn.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGggN7Gqek"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="m98gijb1j"/><path class="t9pa4cczn"/></g></mask></defs><circle mask="url(#SVGggN7Gqek)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:hash-circle-filled" /></template>

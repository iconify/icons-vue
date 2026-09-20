<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/i/icl1jzigc.css';
import '../../css/m/mwe76sblb.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGVkdGvbVu"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="icl1jzigc"/><path class="mwe76sblb"/></g></mask></defs><circle mask="url(#SVGVkdGvbVu)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:flag-straight-circle-filled" /></template>

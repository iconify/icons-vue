<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/byuwc6cgy.css';
import '../../css/b/bc9n_eqle.css';
import '../../css/o/oh_dgz1af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="byuwc6cgy"/><circle class="bc9n_eqle"/><circle class="oh_dgz1af"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:case-lower" /></template>

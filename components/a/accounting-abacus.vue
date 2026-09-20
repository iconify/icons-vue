<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xas18pb7n.css';
import '../../css/o/o_jac7o0o.css';
import '../../css/k/k5lm9_b8y.css';
import '../../css/z/zwcc34jgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xas18pb7n"/><path class="o_jac7o0o"/><path class="k5lm9_b8y"/><path class="zwcc34jgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:accounting-abacus" /></template>

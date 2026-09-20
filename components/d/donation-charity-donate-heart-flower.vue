<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vnw5jbcnp.css';
import '../../css/j/j4jx0sbkj.css';
import '../../css/m/makbbdc0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vnw5jbcnp"/><path class="j4jx0sbkj"/><path class="makbbdc0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:donation-charity-donate-heart-flower" /></template>

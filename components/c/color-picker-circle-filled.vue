<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/i/ivjvz2eii.css';
import '../../css/p/p26na6bbu.css';
import '../../css/u/u4zo_4b1u.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGeWPkve4h"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="p26na6bbu"/><path class="u4zo_4b1u"/></g></mask></defs><circle mask="url(#SVGeWPkve4h)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:color-picker-circle-filled" /></template>

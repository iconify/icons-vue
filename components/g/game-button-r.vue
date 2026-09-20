<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-1hgmmpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-r" /></template>
<style>
.a-1hgmmpc {
  fill: currentColor;
  d: path("M9.721 15.096h.856v-2.473h1.175l1.556 2.473h.99l-1.723-2.686q.623-.218.938-.646q.314-.43.314-1.058q0-.933-.575-1.377t-1.733-.445H9.721zm.856-3.229V9.706l.887-.006q.707-.006 1.092.275q.385.28.385.787q0 .53-.384.818t-1.082.287zM3 19V8.27q0-1.362.973-2.326q.973-.963 2.354-.963h11.346q1.38 0 2.354.963Q21 6.908 21 8.27V19z");
}

</style>

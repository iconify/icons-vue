<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9gsl6b1j.css';
import '../../css/v/vb6su3tol.css';
import '../../css/k/k1xtew5eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9gsl6b1j"/><path class="vb6su3tol"/><path class="k1xtew5eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:database" /></template>

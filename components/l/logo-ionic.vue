<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7_b83bfo.css';
import '../../css/w/w6uz2sbpd.css';
import '../../css/e/epr-bjb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7_b83bfo"/><circle class="w6uz2sbpd"/><path class="epr-bjb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-ionic" /></template>

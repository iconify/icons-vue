<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/c/ciagsr8-s.css';
import '../../css/e/e2otlubpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="ciagsr8-s"/><path class="e2otlubpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:barcode-outline" /></template>

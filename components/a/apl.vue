<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gufcdpbgn.css';
import '../../css/o/oxn1-zbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gufcdpbgn"/><path class="oxn1-zbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apl" /></template>

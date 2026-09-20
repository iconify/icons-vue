<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c1b4tva5l.css';
import '../../css/c/cefjig1hz.css';
import '../../css/y/ygox79bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c1b4tva5l"/><path class="cefjig1hz"/><circle class="ygox79bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lock" /></template>

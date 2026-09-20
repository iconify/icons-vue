<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftl1fs6jj.css';
import '../../css/f/fv1vecnlt.css';
import '../../css/f/flan3pe2x.css';
import '../../css/a/ak5u0_npi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftl1fs6jj"/><path class="fv1vecnlt"/><path clip-rule="evenodd" class="flan3pe2x"/><path clip-rule="evenodd" class="ak5u0_npi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iammeter-dark" /></template>

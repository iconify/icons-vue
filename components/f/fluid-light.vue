<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1ctc1phm.css';
import '../../css/y/ypchirliy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ctc1phm"/><path class="ypchirliy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:fluid-light" /></template>

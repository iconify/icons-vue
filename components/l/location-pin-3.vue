<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q2y7eorwr.css';
import '../../css/b/bjb9rabxp.css';
import '../../css/y/y9coysbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q2y7eorwr"/><path class="bjb9rabxp"/><path class="y9coysbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:location-pin-3" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fthgilgrb.css';
import '../../css/y/yhd0eaczw.css';
import '../../css/z/z8wtxdbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fthgilgrb"/><path class="yhd0eaczw"/><path class="z8wtxdbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kamiyomu-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itw1ckbiw.css';
import '../../css/g/gryaribnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itw1ckbiw"/><path class="gryaribnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloudy-night-outline" /></template>

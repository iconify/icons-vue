<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg2mv0bwm.css';
import '../../css/x/x9xdhqbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg2mv0bwm"/><path class="x9xdhqbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-10-filled" /></template>

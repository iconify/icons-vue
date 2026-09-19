<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3hv07b8e.css';
import '../../css/o/owxry0bls.css';
import '../../css/k/ktqbxi-uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i3hv07b8e"/><path class="owxry0bls"/><path class="ktqbxi-uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-more" /></template>

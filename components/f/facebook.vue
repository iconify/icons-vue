<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgjnt5bfz.css';
import '../../css/y/y08ndqbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgjnt5bfz"/><path class="y08ndqbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:facebook" /></template>

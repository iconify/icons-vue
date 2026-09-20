<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu23jnb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="iu23jnb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:lodging-11" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elzab8bky.css';
import '../../css/f/funyg-b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="elzab8bky"/><path class="funyg-b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:continuwuity-light" /></template>

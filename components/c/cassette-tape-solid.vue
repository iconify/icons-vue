<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swoo4rbsl.css';
import '../../css/u/ukyr80b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swoo4rbsl"/><path class="ukyr80b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cassette-tape-solid" /></template>

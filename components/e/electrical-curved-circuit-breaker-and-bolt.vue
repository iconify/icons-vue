<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2c56nb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g2c56nb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:electrical-curved-circuit-breaker-and-bolt" /></template>

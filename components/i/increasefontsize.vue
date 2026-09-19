<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6mdaccda.css';
import '../../css/m/m79b16c6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6mdaccda"/><path class="m79b16c6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:increasefontsize" /></template>

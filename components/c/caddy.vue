<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8tbmnbml.css';
import '../../css/k/k-c9kibht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8tbmnbml"/><path class="k-c9kibht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caddy" /></template>

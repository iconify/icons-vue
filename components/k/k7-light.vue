<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3ls-9p3k.css';
import '../../css/j/jnr5slbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3ls-9p3k"/><path class="jnr5slbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:k7-light" /></template>

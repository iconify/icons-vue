<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqkghtbcd.css';
import '../../css/j/jnr5slbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqkghtbcd"/><path class="jnr5slbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:k7-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfth_183n.css';
import '../../css/h/h4y9kdbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfth_183n"/><path class="h4y9kdbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lemmy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed6azwwva.css';
import '../../css/k/k65ziybib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ed6azwwva"/><path class="k65ziybib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:geeftlist" /></template>

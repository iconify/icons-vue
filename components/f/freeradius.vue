<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9jd4lb3h.css';
import '../../css/q/qx2necw3z.css';
import '../../css/f/fifs5bbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9jd4lb3h"/><circle class="qx2necw3z"/><path class="fifs5bbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeradius" /></template>

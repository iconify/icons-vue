<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcp9_yb1l.css';
import '../../css/l/lgxe0o1ax.css';
import '../../css/t/tm9f74uep.css';
import '../../css/l/l_q0npboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jcp9_yb1l"/><g class="lgxe0o1ax"><circle class="tm9f74uep"/><path class="l_q0npboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:business-contact" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nevv_l36w.css';
import '../../css/g/gtg8rbctr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nevv_l36w"/><path class="gtg8rbctr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-hr" /></template>

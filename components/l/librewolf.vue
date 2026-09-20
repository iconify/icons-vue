<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkdzwwbtq.css';
import '../../css/r/rzcvymb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="nkdzwwbtq"/><path class="rzcvymb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librewolf" /></template>

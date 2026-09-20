<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm0xpbe5i.css';
import '../../css/s/sla_3qh9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hm0xpbe5i"/><path class="sla_3qh9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fandom" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5biwmbup.css';
import '../../css/g/gjgzt7bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5biwmbup"/><path class="gjgzt7bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etherpad-light" /></template>

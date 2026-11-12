<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcdlw7auy.css';
import '../../css/s/s_jmxibuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="kcdlw7auy"/><path class="s_jmxibuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intervals-icu" /></template>

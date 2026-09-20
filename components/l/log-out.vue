<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4r5-ok7c.css';
import '../../css/a/an49idj0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n4r5-ok7c"/><path class="an49idj0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:log-out" /></template>

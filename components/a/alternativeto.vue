<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrkewab2c.css';
import '../../css/b/b7h45cb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vrkewab2c"/><path class="b7h45cb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alternativeto" /></template>

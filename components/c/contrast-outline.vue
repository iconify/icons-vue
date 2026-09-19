<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k71by3b1k.css';
import '../../css/o/obq3yybhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="k71by3b1k"/><path class="obq3yybhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:contrast-outline" /></template>

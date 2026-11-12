<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9686ab6o.css';
import '../../css/o/o4k3kffuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9686ab6o"/><path class="o4k3kffuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lumio-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r22fqh72r.css';
import '../../css/o/o4k3kffuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r22fqh72r"/><path class="o4k3kffuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lumio-light" /></template>

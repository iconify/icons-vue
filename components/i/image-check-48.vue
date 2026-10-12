<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohjz-yepi.css';
import '../../css/x/xpv1ecudo.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohjz-yepi"/><path class="xpv1ecudo"/><path class="f5bqv3-2b"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-check-48" /></template>

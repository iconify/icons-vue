<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaqgtyjjh.css';
import '../../css/s/sthll3b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kaqgtyjjh"/><path class="sthll3b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:autocaliweb" /></template>

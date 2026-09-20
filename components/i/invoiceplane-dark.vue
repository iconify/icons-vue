<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5yu1qb-n.css';
import '../../css/t/tmnoc9bjp.css';
import '../../css/z/zeq616bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5yu1qb-n"/><path class="tmnoc9bjp"/><path class="zeq616bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceplane-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee3_s121s.css';
import '../../css/x/xyl9rzbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ee3_s121s"/><path class="xyl9rzbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedpushr" /></template>

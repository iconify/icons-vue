<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwsftlbby.css';
import '../../css/n/n-9-1s2vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwsftlbby"/><path class="n-9-1s2vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gosuki" /></template>

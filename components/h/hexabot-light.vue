<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmnvtlv-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmnvtlv-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hexabot-light" /></template>

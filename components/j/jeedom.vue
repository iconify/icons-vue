<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf8n7mb7y.css';
import '../../css/z/zcurb14eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wf8n7mb7y"/><path class="zcurb14eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jeedom" /></template>

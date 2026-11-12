<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxo_cab5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jxo_cab5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hollo" /></template>

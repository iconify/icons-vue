<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdkemcbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdkemcbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:caret-right" /></template>

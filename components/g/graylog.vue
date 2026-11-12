<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2zo4xxmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2zo4xxmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graylog" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ywkvrys.css';
import '../../css/v/vzun6nk-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9ywkvrys"/><path class="vzun6nk-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gathio-light" /></template>

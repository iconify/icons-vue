<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xllod5uya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xllod5uya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudbeaver" /></template>

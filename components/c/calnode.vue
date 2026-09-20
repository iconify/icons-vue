<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daxysxbef.css';
import '../../css/y/y0oobqogr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="daxysxbef"/><path class="y0oobqogr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calnode" /></template>

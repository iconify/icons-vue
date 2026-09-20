<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9618xbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n9618xbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atria" /></template>

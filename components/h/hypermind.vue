<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl80vxbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl80vxbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hypermind" /></template>

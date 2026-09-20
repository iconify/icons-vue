<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6m02jbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6m02jbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komodo-cd-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btoo07bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="btoo07bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:barkeep-light" /></template>

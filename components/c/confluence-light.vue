<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-k0xoma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-k0xoma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:confluence-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf-25ebtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf-25ebtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caderno-light" /></template>

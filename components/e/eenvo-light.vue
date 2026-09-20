<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igog1ebsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igog1ebsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eenvo-light" /></template>

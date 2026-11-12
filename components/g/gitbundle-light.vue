<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdtm0qhix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdtm0qhix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitbundle-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjqtnac9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjqtnac9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:itsm-ng-light" /></template>

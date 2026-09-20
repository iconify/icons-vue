<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shya_ld1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shya_ld1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:itsm-ng-light" /></template>

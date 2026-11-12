<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h63q1abgr.css';
import '../../css/g/g74ykvjvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h63q1abgr"/><path class="g74ykvjvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koel-dark" /></template>

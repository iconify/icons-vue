<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt9ppcjum.css';
import '../../css/a/au4zb9b5u.css';
import '../../css/z/zeq616bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yt9ppcjum"/><path class="au4zb9b5u"/><path class="zeq616bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceplane-dark" /></template>

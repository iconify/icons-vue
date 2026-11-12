<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyemvd5bc.css';
import '../../css/k/k5155bffp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyemvd5bc"/><path class="k5155bffp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eonvelope-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz5qhoa4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz5qhoa4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authentik-light" /></template>

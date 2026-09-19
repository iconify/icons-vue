<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj49vpb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="kj49vpb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-phone" /></template>

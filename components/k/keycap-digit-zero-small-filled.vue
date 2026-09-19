<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx-u50amq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gx-u50amq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-zero-small-filled" /></template>

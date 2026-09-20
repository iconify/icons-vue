<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh4z5kbri.css';
import '../../css/y/y2a9lnbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vh4z5kbri"/><circle class="y2a9lnbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:livinity" /></template>

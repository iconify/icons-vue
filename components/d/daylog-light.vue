<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guzj9glux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guzj9glux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daylog-light" /></template>

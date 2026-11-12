<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnrkj8hrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gnrkj8hrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dji-logbook-dark" /></template>

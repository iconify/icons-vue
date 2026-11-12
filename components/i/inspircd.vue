<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l954m5b7x.css';
import '../../css/l/lvqwy803y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l954m5b7x"/><path class="lvqwy803y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inspircd" /></template>

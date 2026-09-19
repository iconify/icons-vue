<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wojiixdgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wojiixdgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arithmetic-one" /></template>

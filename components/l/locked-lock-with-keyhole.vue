<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unm720e2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="unm720e2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:locked-lock-with-keyhole" /></template>

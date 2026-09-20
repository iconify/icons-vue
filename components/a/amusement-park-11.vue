<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p295tee_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="p295tee_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:amusement-park-11" /></template>

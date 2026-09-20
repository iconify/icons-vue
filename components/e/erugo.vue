<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmjlz_b5w.css';
import '../../css/f/f-tq-dhdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jmjlz_b5w"/><path class="f-tq-dhdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:erugo" /></template>

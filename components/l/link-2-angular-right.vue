<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3irtcyzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="h3irtcyzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:link-2-angular-right" /></template>

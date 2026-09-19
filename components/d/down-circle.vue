<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4w2kqawh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="n4w2kqawh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:down-circle" /></template>

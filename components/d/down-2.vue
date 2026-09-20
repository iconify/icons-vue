<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq92k6g1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq92k6g1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:down-2" /></template>

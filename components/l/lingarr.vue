<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-b8rwb9q.css';
import '../../css/l/llyqf3b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o-b8rwb9q"/><path class="llyqf3b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lingarr" /></template>

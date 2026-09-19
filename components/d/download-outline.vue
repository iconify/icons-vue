<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocod4qb4r.css';
import '../../css/x/xyfijqb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocod4qb4r"/><path class="xyfijqb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:download-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru3berbsx.css';
import '../../css/x/x0sa_-lyq.css';
import '../../css/b/bd4fsf3wr.css';
import '../../css/k/koiau4b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ru3berbsx"/><path class="x0sa_-lyq"/><path class="bd4fsf3wr"/><path class="koiau4b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anchor-48" /></template>

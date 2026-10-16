<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae3ox-mnm.css';
import '../../css/p/pook9-t4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ae3ox-mnm"/><path class="pook9-t4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-boiler-48-bold" /></template>

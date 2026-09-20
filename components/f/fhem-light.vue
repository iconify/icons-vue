<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvpihrqbl.css';
import '../../css/b/bocz3tbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pvpihrqbl"/><path class="bocz3tbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fhem-light" /></template>

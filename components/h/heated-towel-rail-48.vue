<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm-t92b-g.css';
import '../../css/s/s-ndftb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tm-t92b-g"/><path class="s-ndftb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heated-towel-rail-48" /></template>

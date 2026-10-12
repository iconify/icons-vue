<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';
import '../../css/s/sxhkbk65k.css';
import '../../css/g/ge-l3dbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="sxhkbk65k"/><path class="ge-l3dbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-circle-up-48-bold" /></template>

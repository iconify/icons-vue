<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkb50fbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pkb50fbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:down-one" /></template>

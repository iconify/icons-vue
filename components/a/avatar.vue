<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbpjll5ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pbpjll5ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:avatar" /></template>

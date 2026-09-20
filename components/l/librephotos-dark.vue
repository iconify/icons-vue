<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8mup3byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8mup3byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librephotos-dark" /></template>

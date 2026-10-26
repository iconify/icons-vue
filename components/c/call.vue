<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acydh6b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="acydh6b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:call" /></template>

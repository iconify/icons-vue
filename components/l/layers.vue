<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srlizxq6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="srlizxq6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:layers" /></template>

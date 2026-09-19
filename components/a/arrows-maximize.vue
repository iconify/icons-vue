<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1xfxt6no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j1xfxt6no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:arrows-maximize" /></template>

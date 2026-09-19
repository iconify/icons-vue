<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-8pbhbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-8pbhbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:folder-success-one" /></template>

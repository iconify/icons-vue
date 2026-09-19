<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vex7ouxjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vex7ouxjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookshelf-02" /></template>

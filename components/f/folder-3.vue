<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqch9n6xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqch9n6xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:folder-3" /></template>

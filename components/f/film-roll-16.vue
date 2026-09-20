<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b15kgtb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b15kgtb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:film-roll-16" /></template>

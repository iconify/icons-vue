<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prjatmbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="prjatmbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edit-circle-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1vh_fbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1vh_fbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-h" /></template>

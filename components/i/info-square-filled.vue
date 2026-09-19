<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pas3bn7jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pas3bn7jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:info-square-filled" /></template>

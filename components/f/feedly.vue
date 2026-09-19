<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oen4v5bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="oen4v5bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:feedly" /></template>

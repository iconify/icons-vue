<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwvs0hbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bwvs0hbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:document" /></template>

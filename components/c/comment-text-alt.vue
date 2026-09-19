<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ktuhjxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="x7ktuhjxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-text-alt" /></template>

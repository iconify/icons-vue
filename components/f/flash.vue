<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86bcdb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="r86bcdb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flash" /></template>

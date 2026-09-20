<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp-9mbckf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wp-9mbckf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:disconnected" /></template>

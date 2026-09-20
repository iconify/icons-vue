<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwqzm5qkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gwqzm5qkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-bottom-left-top-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik7l-vbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ik7l-vbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gasoline-pump-with-d" /></template>

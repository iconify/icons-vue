<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h95qwns3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h95qwns3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bell" /></template>

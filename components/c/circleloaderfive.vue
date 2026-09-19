<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de3zcmpjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="de3zcmpjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleloaderfive" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzccdua2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yzccdua2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:format-bold-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7ev4k4sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b7ev4k4sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:function-linear-16" /></template>

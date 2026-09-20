<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brfbl6fbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="brfbl6fbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eye-crossed-16" /></template>

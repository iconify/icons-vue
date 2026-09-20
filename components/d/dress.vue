<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-mgfz0ds.css';
import '../../css/m/m-lu0swiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b-mgfz0ds"/><path class="m-lu0swiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dress" /></template>

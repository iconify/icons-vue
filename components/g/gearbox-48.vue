<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwnut8bui.css';
import '../../css/t/tag_xcyrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xwnut8bui"/><path class="tag_xcyrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gearbox-48" /></template>

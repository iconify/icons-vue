<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccj7lubgn.css';
import '../../css/j/j94gsjbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":234};
const content = `<path class="ccj7lubgn"/><path class="j94gsjbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dreamweaver" /></template>

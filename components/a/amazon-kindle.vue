<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow_1ol8gw.css';
import '../../css/c/c27sm6bel.css';
import '../../css/o/o3_oddivz.css';
import '../../css/j/j79e0y2ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":388,"height":86};
const content = `<path clip-rule="evenodd" class="ow_1ol8gw"/><path clip-rule="evenodd" class="c27sm6bel"/><path clip-rule="evenodd" class="o3_oddivz"/><path class="j79e0y2ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amazon-kindle" /></template>

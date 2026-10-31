<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/l1ycygiru.css';
import '../../css/j/jqrzwrb5v.css';
import '../../css/y/y2iwx1nyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="l1ycygiru wm-shadow"/><path class="jqrzwrb5v wm-shadow"/><path class="y2iwx1nyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:japanese-yen" /></template>

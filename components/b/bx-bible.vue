<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmvtqzacp.css';
import '../../css/a/a-jxqyhlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmvtqzacp"/><path class="a-jxqyhlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bible" /></template>

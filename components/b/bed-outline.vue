<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpw0hrbqk.css';
import '../../css/z/zdracac6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lpw0hrbqk"/><path class="zdracac6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bed-outline" /></template>

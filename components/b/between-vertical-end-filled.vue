<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykz2nk03s.css';
import '../../css/w/w4_yefglu.css';
import '../../css/a/ag06jb7os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykz2nk03s"/><rect class="w4_yefglu"/><rect class="ag06jb7os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:between-vertical-end-filled" /></template>

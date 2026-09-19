<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru9ga46bg.css';
import '../../css/b/bii6hxbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru9ga46bg"/><path clip-rule="evenodd" class="bii6hxbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:clock" /></template>

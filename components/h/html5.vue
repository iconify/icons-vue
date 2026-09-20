<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_sjz8b4l.css';
import '../../css/c/c080srerl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_sjz8b4l"/><path class="c080srerl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:html5" /></template>

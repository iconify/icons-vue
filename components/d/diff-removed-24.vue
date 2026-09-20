<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6_y8wh0z.css';
import '../../css/c/c485hsbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6_y8wh0z"/><path class="c485hsbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-removed-24" /></template>

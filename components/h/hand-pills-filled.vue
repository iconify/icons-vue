<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6j4vc5th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6j4vc5th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-pills-filled" /></template>

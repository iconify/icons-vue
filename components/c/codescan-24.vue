<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3wi9ouxj.css';
import '../../css/y/ykjnrse8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3wi9ouxj"/><path class="ykjnrse8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codescan-24" /></template>

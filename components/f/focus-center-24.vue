<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi8jfjbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi8jfjbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:focus-center-24" /></template>

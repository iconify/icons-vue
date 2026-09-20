<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukm4dob-t.css';
import '../../css/y/yh-c-kbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ukm4dob-t"/><path class="yh-c-kbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:entertainment-events-hobbies-popcorn" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra7rlfb9o.css';
import '../../css/a/a1ufk92yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ra7rlfb9o"/><path class="a1ufk92yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-laboratory-test-blood-sugar" /></template>

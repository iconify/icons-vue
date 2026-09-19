<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om4mwxbqv.css';
import '../../css/i/i4ou1xbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="om4mwxbqv"/><path class="i4ou1xbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:karma" /></template>

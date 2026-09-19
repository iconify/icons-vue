<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk-u7ac7z.css';
import '../../css/h/h3iug1uno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pk-u7ac7z"/><path class="h3iug1uno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:lodash" /></template>

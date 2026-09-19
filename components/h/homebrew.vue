<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2zfbfbns.css';
import '../../css/m/m8_yakbvd.css';
import '../../css/w/wurw0faww.css';
import '../../css/m/mt8xaybfz.css';
import '../../css/x/x0jgdesyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c2zfbfbns"/><path class="m8_yakbvd"/><path class="wurw0faww"/><path class="mt8xaybfz"/><path class="x0jgdesyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:homebrew" /></template>

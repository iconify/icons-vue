<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvfl6rbyb.css';
import '../../css/i/iu8u25bgh.css';
import '../../css/c/cvkuub02k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lvfl6rbyb"/><path class="iu8u25bgh"/><path class="cvkuub02k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:git-wordmark" /></template>

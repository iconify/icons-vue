<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdptjablm.css';
import '../../css/r/rh99p0mbj.css';
import '../../css/b/b27n8hp7k.css';
import '../../css/y/yg15a6-lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="tdptjablm"><path clip-rule="evenodd" class="rh99p0mbj"/><path class="b27n8hp7k"/></g><path class="yg15a6-lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:github-wordmark" /></template>

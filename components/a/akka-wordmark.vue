<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb_6iza3u.css';
import '../../css/g/gi3nmwdkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gb_6iza3u"/><path class="gi3nmwdkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:akka-wordmark" /></template>

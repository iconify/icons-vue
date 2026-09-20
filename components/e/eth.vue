<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dor-qnbot.css';
import '../../css/u/uzfziisgz.css';
import '../../css/j/jv7_enpyu.css';
import '../../css/i/inlew3bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dor-qnbot"/><path class="uzfziisgz"/><path clip-rule="evenodd" class="jv7_enpyu"/><path clip-rule="evenodd" class="inlew3bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eth" /></template>

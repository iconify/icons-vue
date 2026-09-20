<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5hhk_blw.css';
import '../../css/x/x03n-xhgu.css';
import '../../css/v/v67m5-lov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5hhk_blw"/><path class="x03n-xhgu"/><path class="v67m5-lov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bithumb" /></template>

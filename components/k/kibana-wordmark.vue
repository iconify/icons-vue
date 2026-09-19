<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc-d2sbgq.css';
import '../../css/y/yk-lniigf.css';
import '../../css/b/b3zmgxb9u.css';
import '../../css/j/j4r7oqbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fc-d2sbgq"/><path class="yk-lniigf"/><path class="b3zmgxb9u"/><path class="j4r7oqbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kibana-wordmark" /></template>

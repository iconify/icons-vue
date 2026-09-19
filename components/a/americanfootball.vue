<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jozfr4bht.css';
import '../../css/b/bgu4qnb1v.css';
import '../../css/d/dbndu9bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jozfr4bht"/><path class="bgu4qnb1v"/><path class="dbndu9bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:americanfootball" /></template>

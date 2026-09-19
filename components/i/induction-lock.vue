<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bco27yqdx.css';
import '../../css/q/qehbpfbew.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXfNetdbU"><g class="wwvp95byt"><path class="bco27yqdx"/><path class="qehbpfbew"/></g></mask></defs><path mask="url(#SVGXfNetdbU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:induction-lock" /></template>

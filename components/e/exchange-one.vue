<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bco27yqdx.css';
import '../../css/i/i0qcow7ud.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQkwBZpuH"><g class="wwvp95byt"><path class="bco27yqdx"/><path class="i0qcow7ud"/></g></mask></defs><path mask="url(#SVGQkwBZpuH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:exchange-one" /></template>

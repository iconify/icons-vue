<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/y/yihstg8dq.css';
import '../../css/y/ygihsgtev.css';
import '../../css/x/xzm23acqn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeKL45lVJ"><g class="hv130ab-t"><path class="yihstg8dq"/><path class="ygihsgtev"/><path class="xzm23acqn"/></g></mask></defs><path mask="url(#SVGeKL45lVJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bowl-one" /></template>

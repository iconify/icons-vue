<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/c/cd0y8fbhg.css';
import '../../css/b/bst2n4bqq.css';
import '../../css/k/ko8634b1x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGd209Vddg"><g class="aql7dnt-u"><path class="cd0y8fbhg"/><circle class="bst2n4bqq"/><circle class="ko8634b1x"/></g></mask></defs><path mask="url(#SVGd209Vddg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:list-fail" /></template>

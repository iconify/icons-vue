<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/ab1-j-jdh.css';
import '../../css/c/cj53yjbsz.css';
import '../../css/y/yig1dlbzd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5rISxenJ"><g class="s9cl3zbei"><path class="ab1-j-jdh"/><path class="cj53yjbsz"/><path class="yig1dlbzd"/></g></mask></defs><path mask="url(#SVG5rISxenJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:file-jpg" /></template>

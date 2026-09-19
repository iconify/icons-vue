<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/y27kjc42t.css';
import '../../css/o/odd5su9rz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5shBabjy"><g class="s9cl3zbei"><path class="y27kjc42t"/><path class="odd5su9rz"/></g></mask></defs><path mask="url(#SVG5shBabjy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:html-five" /></template>

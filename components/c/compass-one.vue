<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/r5tlskk2v.css';
import '../../css/y/y_x-crbnf.css';
import '../../css/a/au_gpv-5l.css';
import '../../css/v/v6w04hs7p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqHRGH4FD"><g class="s9cl3zbei"><path class="r5tlskk2v"/><path class="y_x-crbnf"/><path class="au_gpv-5l"/><path class="v6w04hs7p"/></g></mask></defs><path mask="url(#SVGqHRGH4FD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:compass-one" /></template>

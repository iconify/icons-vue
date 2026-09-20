<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad53olvua.css';
import '../../css/z/zenn7i8an.css';
import '../../css/b/bi4q1fb5h.css';
import '../../css/d/dznxpfe5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<g class="ad53olvua"><path class="zenn7i8an"/><path class="bi4q1fb5h"/><path class="dznxpfe5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:haskell" /></template>

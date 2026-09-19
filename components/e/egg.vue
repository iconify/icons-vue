<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/rniplklmo.css';
import '../../css/a/a9vmhrz8t.css';
import '../../css/k/kntuwjb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="rniplklmo"/><path class="a9vmhrz8t"/><path class="kntuwjb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:egg" /></template>

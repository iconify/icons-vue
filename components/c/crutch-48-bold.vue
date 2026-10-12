<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udwer-bvl.css';
import '../../css/j/jcdaq3bjh.css';
import '../../css/a/a4d54xg-r.css';
import '../../css/d/du3a-kbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udwer-bvl"/><path class="jcdaq3bjh"/><path class="a4d54xg-r"/><path class="du3a-kbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crutch-48-bold" /></template>

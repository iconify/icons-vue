<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmnrj9_6h.css';
import '../../css/l/lrkaywonk.css';
import '../../css/a/auxtjjb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kmnrj9_6h"/><path class="lrkaywonk"/><path class="auxtjjb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-webpack-open" /></template>

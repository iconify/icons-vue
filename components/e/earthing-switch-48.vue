<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2o-q5bqy.css';
import '../../css/v/v51dofb5w.css';
import '../../css/r/rsiohj6qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c2o-q5bqy"/><path class="v51dofb5w"/><path class="rsiohj6qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthing-switch-48" /></template>

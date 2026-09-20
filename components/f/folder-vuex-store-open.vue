<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-qxuibhr.css';
import '../../css/l/lxtaj1b-t.css';
import '../../css/t/tx-n4du-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-qxuibhr"/><path class="lxtaj1b-t"/><path class="tx-n4du-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vuex-store-open" /></template>

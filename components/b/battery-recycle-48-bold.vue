<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abdw3sbya.css';
import '../../css/l/lpjx8vm8f.css';
import '../../css/d/d4fb8-n_r.css';
import '../../css/v/v0q86cqji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="abdw3sbya"/><path class="lpjx8vm8f"/><path class="d4fb8-n_r"/><path class="v0q86cqji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-recycle-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ersub-k.css';
import '../../css/b/bpoutcsqa.css';
import '../../css/v/v_i9e3d-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x4ersub-k"/><path class="bpoutcsqa"/><path class="v_i9e3d-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-pull-request-48" /></template>

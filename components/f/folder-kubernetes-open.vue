<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q90-1_bvc.css';
import '../../css/q/qqn7q5bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q90-1_bvc"/><path class="qqn7q5bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-kubernetes-open" /></template>

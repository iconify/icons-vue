<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tta3otbad.css';
import '../../css/z/zza0bbbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tta3otbad"/><path class="zza0bbbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-skills-open" /></template>

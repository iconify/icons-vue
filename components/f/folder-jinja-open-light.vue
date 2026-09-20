<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnxr3dbjd.css';
import '../../css/x/x4maqhbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bnxr3dbjd"/><path class="x4maqhbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-jinja-open-light" /></template>

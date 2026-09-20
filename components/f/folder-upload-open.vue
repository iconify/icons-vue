<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi9dt8sqd.css';
import '../../css/a/aewpyo09j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vi9dt8sqd"/><path class="aewpyo09j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-upload-open" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq27ugb2z.css';
import '../../css/l/lhog0tb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cq27ugb2z"/><path class="lhog0tb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-firebase-open" /></template>

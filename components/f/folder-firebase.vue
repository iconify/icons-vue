<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsuo4vbmg.css';
import '../../css/l/lhog0tb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nsuo4vbmg"/><path class="lhog0tb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-firebase" /></template>

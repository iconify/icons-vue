<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1crshb5u.css';
import '../../css/b/byrocu6aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h1crshb5u"/><path class="byrocu6aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-direnv-open" /></template>

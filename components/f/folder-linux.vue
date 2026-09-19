<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3ugng94a.css';
import '../../css/d/dcz5ovbjt.css';
import '../../css/k/kyml_y7yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w3ugng94a"/><path class="dcz5ovbjt"/><path class="kyml_y7yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-linux" /></template>

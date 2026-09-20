<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvx3k5b5o.css';
import '../../css/f/f3yq4bbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvx3k5b5o"/><path class="f3yq4bbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:clear" /></template>

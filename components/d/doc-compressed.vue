<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkszhcp6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lkszhcp6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-compressed" /></template>

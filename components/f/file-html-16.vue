<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqxn57b_e.css';
import '../../css/r/rnvgnfbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kqxn57b_e"/><path clip-rule="evenodd" class="rnvgnfbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:file-html-16" /></template>

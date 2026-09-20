<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnxtu2a1f.css';
import '../../css/p/pt_8qebbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wnxtu2a1f"/><path clip-rule="evenodd" class="pt_8qebbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cutter-16" /></template>

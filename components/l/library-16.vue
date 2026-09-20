<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r31ezd-mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r31ezd-mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:library-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9dm_5b8b.css';
import '../../css/x/x6d1mvvmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j9dm_5b8b"/><path class="x6d1mvvmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:lightbulb" /></template>

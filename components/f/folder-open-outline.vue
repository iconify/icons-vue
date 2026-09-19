<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oznaotbtq.css';
import '../../css/z/z8vf7-egw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oznaotbtq"/><path class="z8vf7-egw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:folder-open-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l46o-ebdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l46o-ebdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:importcontacts" /></template>

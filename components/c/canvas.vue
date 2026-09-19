<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok9qob__s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ok9qob__s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:canvas" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycy_tv9yp.css';
import '../../css/n/n5h7sdi6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ycy_tv9yp"/><path class="n5h7sdi6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:golang" /></template>

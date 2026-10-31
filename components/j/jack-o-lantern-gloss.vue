<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt9rf2bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt9rf2bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jack-o-lantern-gloss" /></template>

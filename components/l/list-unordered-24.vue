<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2p0nnb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2p0nnb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:list-unordered-24" /></template>

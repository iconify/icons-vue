<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgfmt1b6e.css';
import '../../css/y/yo3cu2bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgfmt1b6e"/><path class="yo3cu2bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-discussion-24" /></template>

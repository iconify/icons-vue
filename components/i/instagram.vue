<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9zur0vky.css';
import '../../css/t/tqgdst6it.css';
import '../../css/d/dyv50c1zz.css';
import '../../css/e/e08bxfbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="z9zur0vky"/><path class="tqgdst6it"/><circle class="dyv50c1zz"/><circle class="e08bxfbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:instagram" /></template>

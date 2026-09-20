<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kim_xpwqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kim_xpwqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-eighth-notes" /></template>

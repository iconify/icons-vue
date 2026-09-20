<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r70_bowor.css';
import '../../css/j/j73_9_mpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r70_bowor"/><path class="j73_9_mpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-arrow-up-light" /></template>

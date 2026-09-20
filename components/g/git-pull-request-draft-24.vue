<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9x4iebyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9x4iebyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-draft-24" /></template>

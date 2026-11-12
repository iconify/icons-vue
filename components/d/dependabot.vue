<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg5zf7b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bg5zf7b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dependabot" /></template>

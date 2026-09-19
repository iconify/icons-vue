<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bee63kb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bee63kb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:css3-wordmark" /></template>

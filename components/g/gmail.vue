<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk3fodb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="tk3fodb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gmail" /></template>

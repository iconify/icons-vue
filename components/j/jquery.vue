<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtp61qt2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jtp61qt2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:jquery" /></template>

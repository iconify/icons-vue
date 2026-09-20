<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8jp68q7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b8jp68q7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:anguished-face-in-circle" /></template>

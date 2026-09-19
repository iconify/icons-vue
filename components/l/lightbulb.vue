<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf0alrb_x.css';
import '../../css/c/ckevorb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bf0alrb_x"/><path class="ckevorb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:lightbulb" /></template>

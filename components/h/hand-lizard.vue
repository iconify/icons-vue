<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwny0ub1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwny0ub1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-lizard" /></template>

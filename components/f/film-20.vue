<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewn1ke3br.css';
import '../../css/x/xxdenrb3z.css';
import '../../css/l/lqnnr9bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="xxdenrb3z"/><path class="lqnnr9bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-20" /></template>

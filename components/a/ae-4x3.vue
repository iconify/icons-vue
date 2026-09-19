<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1xzrlbhy.css';
import '../../css/v/v18c9fbau.css';
import '../../css/r/r38kscbse.css';
import '../../css/j/jlqxt-bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="o1xzrlbhy"/><path class="v18c9fbau"/><path class="r38kscbse"/><path class="jlqxt-bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ae-4x3" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex9s0kk5d.css';
import '../../css/p/pvjrmx88k.css';
import '../../css/l/l7w7mb29j.css';
import '../../css/f/f9ihxbcgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ex9s0kk5d"/><path class="pvjrmx88k"/><path class="l7w7mb29j"/><path class="f9ihxbcgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:kyrgyzstan" /></template>

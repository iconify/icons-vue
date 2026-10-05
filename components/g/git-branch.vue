<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/u59vj0byr.css';
import '../../css/p/pvyu0vgcm.css';
import '../../css/b/b5sne2bxw.css';
import '../../css/i/ipsrlibww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="u59vj0byr"/><path class="pvyu0vgcm"/><path class="b5sne2bxw"/><path class="ipsrlibww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:git-branch" /></template>

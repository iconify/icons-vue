<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm9larbcx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ebyo9fyqg.css';
import '../../css/j/j4pzf9bzr.css';
import '../../css/r/r39x_21mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm9larbcx secondary"/><g class="dt0cm9dhy primary"><path class="ebyo9fyqg"/><path class="j4pzf9bzr"/><path class="r39x_21mf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:blocks-duo" /></template>

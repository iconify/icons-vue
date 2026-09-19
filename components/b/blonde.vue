<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvck1-bja.css';
import '../../css/e/e0-er9n5v.css';
import '../../css/c/cpu5x_b6u.css';
import '../../css/w/wi9pnybkj.css';
import '../../css/f/fjuavqbkc.css';
import '../../css/f/f63f7jy9v.css';
import '../../css/g/gj8rdy9lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nvck1-bja"/><path class="e0-er9n5v"/><path class="cpu5x_b6u"/><path class="wi9pnybkj"/><path class="fjuavqbkc"/><path class="f63f7jy9v"/><path class="gj8rdy9lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blonde" /></template>

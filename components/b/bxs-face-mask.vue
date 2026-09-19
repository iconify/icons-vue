<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kibzxxbgb.css';
import '../../css/p/pjyeu65td.css';
import '../../css/h/hcj6o-bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kibzxxbgb"/><circle class="pjyeu65td"/><circle class="hcj6o-bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-face-mask" /></template>

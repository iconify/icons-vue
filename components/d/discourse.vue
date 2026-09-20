<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1jccbn5h.css';
import '../../css/t/tmvilxb0i.css';
import '../../css/f/fnmjwhxeg.css';
import '../../css/n/n4-4ubchv.css';
import '../../css/k/kkfn5ab0r.css';
import '../../css/m/muy82sb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<path class="u1jccbn5h"/><path class="tmvilxb0i"/><path class="fnmjwhxeg"/><path class="n4-4ubchv"/><path class="kkfn5ab0r"/><path class="muy82sb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:discourse" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnboovlfn.css';
import '../../css/c/c-h-kzbwd.css';
import '../../css/g/giut3nb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mnboovlfn"/><path class="c-h-kzbwd"/><path class="giut3nb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-stopwatch" /></template>

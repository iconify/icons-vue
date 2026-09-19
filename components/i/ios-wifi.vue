<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwwxm2b6y.css';
import '../../css/j/j8adrjbzg.css';
import '../../css/k/ken9h11xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwwxm2b6y"/><path class="j8adrjbzg"/><path class="ken9h11xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-wifi" /></template>

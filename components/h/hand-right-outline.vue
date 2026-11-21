<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnjtaqb5l.css';
import '../../css/z/zogbbpbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jnjtaqb5l"/><path class="zogbbpbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hand-right-outline" /></template>

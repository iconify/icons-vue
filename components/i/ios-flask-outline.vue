<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghy9vobgd.css';
import '../../css/b/bqzzynbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghy9vobgd"/><path class="bqzzynbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-flask-outline" /></template>

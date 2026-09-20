<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgs1axbkw.css';
import '../../css/f/f3yq4bbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pgs1axbkw"/><path class="f3yq4bbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:info" /></template>

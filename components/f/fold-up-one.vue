<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxotp5bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oxotp5bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:fold-up-one" /></template>

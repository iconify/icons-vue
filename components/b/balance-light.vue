<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry6canfiv.css';
import '../../css/r/re9d9lkhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry6canfiv"/><path class="re9d9lkhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:balance-light" /></template>

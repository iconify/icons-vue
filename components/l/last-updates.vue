<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t19_d8l-n.css';
import '../../css/u/u7aldsb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t19_d8l-n"/><path class="u7aldsb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:last-updates" /></template>

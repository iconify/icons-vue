<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_8vpzbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e_8vpzbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:favourite" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdvrx72kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pdvrx72kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffee-mug-with-steam" /></template>

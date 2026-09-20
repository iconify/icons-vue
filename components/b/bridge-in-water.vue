<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqumhyl1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kqumhyl1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bridge-in-water" /></template>
